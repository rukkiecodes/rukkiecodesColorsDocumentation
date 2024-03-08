<template>
    <h3 class="mt-10">Indigo</h3>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ indigo50.name }}</td>
                <td>{{ indigo50.hex }}</td>
                <td>
                    <v-sheet :color="indigo50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo100.name }}</td>
                <td>{{ indigo100.hex }}</td>
                <td>
                    <v-sheet :color="indigo100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo200.name }}</td>
                <td>{{ indigo200.hex }}</td>
                <td>
                    <v-sheet :color="indigo200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo300.name }}</td>
                <td>{{ indigo300.hex }}</td>
                <td>
                    <v-sheet :color="indigo300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo400.name }}</td>
                <td>{{ indigo400.hex }}</td>
                <td>
                    <v-sheet :color="indigo400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo500.name }}</td>
                <td>{{ indigo500.hex }}</td>
                <td>
                    <v-sheet :color="indigo500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo600.name }}</td>
                <td>{{ indigo600.hex }}</td>
                <td>
                    <v-sheet :color="indigo600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo700.name }}</td>
                <td>{{ indigo700.hex }}</td>
                <td>
                    <v-sheet :color="indigo700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo800.name }}</td>
                <td>{{ indigo800.hex }}</td>
                <td>
                    <v-sheet :color="indigo800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ indigo900.name }}</td>
                <td>{{ indigo900.hex }}</td>
                <td>
                    <v-sheet :color="indigo900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    indigo50,
    indigo100,
    indigo200,
    indigo300,
    indigo400,
    indigo500,
    indigo600,
    indigo700,
    indigo800,
    indigo900,
} from 'rukkiecodes-colors';
</script>
