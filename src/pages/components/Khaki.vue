<template>
    <h3 class="mt-10">Khaki</h3>
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
                <td>{{ khaki50.name }}</td>
                <td>{{ khaki50.hex }}</td>
                <td>
                    <v-sheet :color="khaki50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki100.name }}</td>
                <td>{{ khaki100.hex }}</td>
                <td>
                    <v-sheet :color="khaki100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki200.name }}</td>
                <td>{{ khaki200.hex }}</td>
                <td>
                    <v-sheet :color="khaki200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki300.name }}</td>
                <td>{{ khaki300.hex }}</td>
                <td>
                    <v-sheet :color="khaki300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki400.name }}</td>
                <td>{{ khaki400.hex }}</td>
                <td>
                    <v-sheet :color="khaki400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki500.name }}</td>
                <td>{{ khaki500.hex }}</td>
                <td>
                    <v-sheet :color="khaki500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki600.name }}</td>
                <td>{{ khaki600.hex }}</td>
                <td>
                    <v-sheet :color="khaki600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki700.name }}</td>
                <td>{{ khaki700.hex }}</td>
                <td>
                    <v-sheet :color="khaki700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki800.name }}</td>
                <td>{{ khaki800.hex }}</td>
                <td>
                    <v-sheet :color="khaki800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ khaki900.name }}</td>
                <td>{{ khaki900.hex }}</td>
                <td>
                    <v-sheet :color="khaki900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    khaki50,
    khaki100,
    khaki200,
    khaki300,
    khaki400,
    khaki500,
    khaki600,
    khaki700,
    khaki800,
    khaki900,
} from 'rukkiecodes-colors';
</script>
