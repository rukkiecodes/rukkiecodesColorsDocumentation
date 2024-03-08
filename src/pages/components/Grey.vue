<template>
    <h3 class="mt-10">Grey</h3>
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
                <td>{{ grey50.name }}</td>
                <td>{{ grey50.hex }}</td>
                <td>
                    <v-sheet :color="grey50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey100.name }}</td>
                <td>{{ grey100.hex }}</td>
                <td>
                    <v-sheet :color="grey100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey200.name }}</td>
                <td>{{ grey200.hex }}</td>
                <td>
                    <v-sheet :color="grey200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey300.name }}</td>
                <td>{{ grey300.hex }}</td>
                <td>
                    <v-sheet :color="grey300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey400.name }}</td>
                <td>{{ grey400.hex }}</td>
                <td>
                    <v-sheet :color="grey400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey500.name }}</td>
                <td>{{ grey500.hex }}</td>
                <td>
                    <v-sheet :color="grey500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey600.name }}</td>
                <td>{{ grey600.hex }}</td>
                <td>
                    <v-sheet :color="grey600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey700.name }}</td>
                <td>{{ grey700.hex }}</td>
                <td>
                    <v-sheet :color="grey700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey800.name }}</td>
                <td>{{ grey800.hex }}</td>
                <td>
                    <v-sheet :color="grey800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ grey900.name }}</td>
                <td>{{ grey900.hex }}</td>
                <td>
                    <v-sheet :color="grey900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    grey50,
    grey100,
    grey200,
    grey300,
    grey400,
    grey500,
    grey600,
    grey700,
    grey800,
    grey900,
} from 'rukkiecodes-colors';
</script>
