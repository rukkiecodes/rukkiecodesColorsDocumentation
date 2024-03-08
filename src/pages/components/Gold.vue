<template>
    <h3 class="mt-10">Gold</h3>
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
                <td>{{ gold50.name }}</td>
                <td>{{ gold50.hex }}</td>
                <td>
                    <v-sheet :color="gold50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold100.name }}</td>
                <td>{{ gold100.hex }}</td>
                <td>
                    <v-sheet :color="gold100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold200.name }}</td>
                <td>{{ gold200.hex }}</td>
                <td>
                    <v-sheet :color="gold200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold300.name }}</td>
                <td>{{ gold300.hex }}</td>
                <td>
                    <v-sheet :color="gold300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold400.name }}</td>
                <td>{{ gold400.hex }}</td>
                <td>
                    <v-sheet :color="gold400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold500.name }}</td>
                <td>{{ gold500.hex }}</td>
                <td>
                    <v-sheet :color="gold500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold600.name }}</td>
                <td>{{ gold600.hex }}</td>
                <td>
                    <v-sheet :color="gold600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold700.name }}</td>
                <td>{{ gold700.hex }}</td>
                <td>
                    <v-sheet :color="gold700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold800.name }}</td>
                <td>{{ gold800.hex }}</td>
                <td>
                    <v-sheet :color="gold800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ gold900.name }}</td>
                <td>{{ gold900.hex }}</td>
                <td>
                    <v-sheet :color="gold900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    gold50,
    gold100,
    gold200,
    gold300,
    gold400,
    gold500,
    gold600,
    gold700,
    gold800,
    gold900,
} from 'rukkiecodes-colors';
</script>
